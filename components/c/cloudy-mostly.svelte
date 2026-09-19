<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/yh1fggbau.css';
import '../../css/o/o_x_kbchi.css';
import '../../css/e/emxd30-sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="yh1fggbau"/><path class="o_x_kbchi"/><path class="emxd30-sb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cloudy-mostly" {...props}></Icon>
