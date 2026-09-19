<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/gdor4w2zf.css';
import '../../css/y/yo65-cb-m.css';
import '../../css/n/n16la8pke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="gdor4w2zf"/><path class="yo65-cb-m"/><path class="n16la8pke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chart-pie" {...props}></Icon>
