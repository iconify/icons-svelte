<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it8r15bsj.css';
import '../../css/r/rk4fbbbyc.css';
import '../../css/p/pneyzwbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="it8r15bsj"/><path class="rk4fbbbyc"/><path class="pneyzwbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paint-roller-20-bold" {...props}></Icon>
