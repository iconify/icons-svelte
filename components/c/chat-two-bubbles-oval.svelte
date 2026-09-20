<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/tpv6aibwy.css';
import '../../css/o/ooztnrzce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="tpv6aibwy"/><path class="ooztnrzce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-two-bubbles-oval" {...props}></Icon>
