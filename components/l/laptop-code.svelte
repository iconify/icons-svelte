<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/txtwnjbdf.css';
import '../../css/z/zm17-uvzv.css';
import '../../css/b/b3e5m_1wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="txtwnjbdf"/><path class="zm17-uvzv"/><path class="b3e5m_1wu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:laptop-code" {...props}></Icon>
