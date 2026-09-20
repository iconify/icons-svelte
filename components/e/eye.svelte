<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/he_-9zvcv.css';
import '../../css/o/ou-f-vnmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="gp_8x1bzb"><path class="he_-9zvcv"/><path class="ou-f-vnmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:eye" {...props}></Icon>
