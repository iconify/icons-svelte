<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3b9dkb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3b9dkb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-outline" {...props}></Icon>
