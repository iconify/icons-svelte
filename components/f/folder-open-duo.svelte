<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rq4j_kx8n.css';
import '../../css/y/yx1cocbxe.css';
import '../../css/y/y2e4jbb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rq4j_kx8n"/><path class="yx1cocbxe"/><path class="y2e4jbb1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:folder-open-duo" {...props}></Icon>
