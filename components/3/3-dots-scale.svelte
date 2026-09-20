<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd9ajlbga.css';
import '../../css/v/vdnqjebwm.css';
import '../../css/x/xj894begb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle r="3" class="qd9ajlbga"><animate id="SVG9IgbRbsl" attributeName="r" begin="0;SVGFUNpCWdG.end-0.25s" dur="0.75s" values="3;.2;3"/></circle><circle r="3" class="vdnqjebwm"><animate attributeName="r" begin="SVG9IgbRbsl.end-0.6s" dur="0.75s" values="3;.2;3"/></circle><circle r="3" class="xj894begb"><animate id="SVGFUNpCWdG" attributeName="r" begin="SVG9IgbRbsl.end-0.45s" dur="0.75s" values="3;.2;3"/></circle>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="svg-spinners:3-dots-scale" {...props}></Icon>
