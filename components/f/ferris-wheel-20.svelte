<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzdy5vbln.css';
import '../../css/g/g483dpl3h.css';
import '../../css/f/fzumlcbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lzdy5vbln"/><path class="g483dpl3h"/><path class="fzumlcbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ferris-wheel-20" {...props}></Icon>
