<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iad3jz0vo.css';
import '../../css/q/qubhqfq4s.css';
import '../../css/a/alepcebtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="iad3jz0vo"/><path clip-rule="evenodd" class="qubhqfq4s"/><path class="alepcebtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hammer-bold" {...props}></Icon>
