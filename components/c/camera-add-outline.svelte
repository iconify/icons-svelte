<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beqvsgsfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="beqvsgsfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-add-outline" {...props}></Icon>
