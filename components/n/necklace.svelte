<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/u/ucne17b7x.css';
import '../../css/o/op6p268fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="ucne17b7x"/><path class="op6p268fa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:necklace" {...props}></Icon>
