<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mdrrxqbio.css';
import '../../css/p/po0uuiouq.css';
import '../../css/a/a_nlxibcr.css';
import '../../css/r/rd_-cebxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="mdrrxqbio"/><path clip-rule="evenodd" class="po0uuiouq"/><path class="a_nlxibcr"/><path class="rd_-cebxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:day-outline" {...props}></Icon>
