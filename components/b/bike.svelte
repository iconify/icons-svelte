<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/ylhx5jbuy.css';
import '../../css/k/kp6x66biy.css';
import '../../css/r/rp-5i7zrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ylhx5jbuy"/><path class="kp6x66biy"/><path class="rp-5i7zrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bike" {...props}></Icon>
