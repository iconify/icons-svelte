<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xqlemybcl.css';
import '../../css/t/tjaak3z0c.css';
import '../../css/j/jo5f2oxyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xqlemybcl"/><path clip-rule="evenodd" class="tjaak3z0c"/><path class="jo5f2oxyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-ring-bold" {...props}></Icon>
