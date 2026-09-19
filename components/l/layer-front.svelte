<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/j/jcog3sb1t.css';
import '../../css/q/qfx3b_qyy.css';
import '../../css/b/bdr13-bav.css';
import '../../css/h/hjrpc0b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="jcog3sb1t"/><path class="qfx3b_qyy"/><path class="bdr13-bav"/><path class="hjrpc0b3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layer-front" {...props}></Icon>
