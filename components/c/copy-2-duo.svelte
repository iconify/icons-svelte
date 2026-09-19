<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u4-kcfbnx.css';
import '../../css/o/o-uvx-bbx.css';
import '../../css/i/ihh_jhb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="u4-kcfbnx"/><path class="o-uvx-bbx"/><path class="ihh_jhb-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:copy-2-duo" {...props}></Icon>
