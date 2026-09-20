<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/ynqmrvbmv.css';
import '../../css/o/ou-f-vnmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="gp_8x1bzb"><path class="ynqmrvbmv"/><path class="ou-f-vnmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:cog-alt" {...props}></Icon>
