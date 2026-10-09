<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jogeij0zr.css';
import '../../css/k/kwe73qles.css';
import '../../css/t/tqkl31bnf.css';
import '../../css/u/uh17zlbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jogeij0zr"/><path class="kwe73qles"/><path class="tqkl31bnf"/><path class="uh17zlbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-plus-20-bold" {...props}></Icon>
