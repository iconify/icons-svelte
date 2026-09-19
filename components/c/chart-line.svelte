<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/i/ibgd_d3-d.css';
import '../../css/t/t0jd4370a.css';
import '../../css/x/xqpkavovk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ibgd_d3-d"/><path class="t0jd4370a"/><path class="xqpkavovk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chart-line" {...props}></Icon>
