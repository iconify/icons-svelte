<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bacfu3bgr.css';
import '../../css/z/zhfv58bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bacfu3bgr"/><path class="zhfv58bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:memory" {...props}></Icon>
