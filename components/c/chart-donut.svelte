<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/i/ino6mr9nn.css';
import '../../css/s/sn6br5b4i.css';
import '../../css/c/csubeabti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ino6mr9nn"/><path class="sn6br5b4i"/><path class="csubeabti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chart-donut" {...props}></Icon>
