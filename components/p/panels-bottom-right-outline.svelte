<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sef_1obna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sef_1obna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-bottom-right-outline" {...props}></Icon>
