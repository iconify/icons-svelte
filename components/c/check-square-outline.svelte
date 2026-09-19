<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vh5znhotu.css';
import '../../css/t/tj4vulnki.css';
import '../../css/t/tkfrl-bwu.css';
import '../../css/q/qff5zwbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vh5znhotu"/><path clip-rule="evenodd" class="tj4vulnki"/><path class="tkfrl-bwu"/><path clip-rule="evenodd" class="qff5zwbcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:check-square-outline" {...props}></Icon>
