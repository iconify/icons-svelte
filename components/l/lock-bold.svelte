<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eedai1u0v.css';
import '../../css/o/otpnsvwdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eedai1u0v"/><path class="otpnsvwdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lock-bold" {...props}></Icon>
