<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/i/ibgd_d3-d.css';
import '../../css/d/duhytsawt.css';
import '../../css/e/eux6wjb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ibgd_d3-d"/><path class="duhytsawt"/><path class="eux6wjb8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chart-line-1" {...props}></Icon>
