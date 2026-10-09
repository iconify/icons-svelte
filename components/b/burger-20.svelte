<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gav8xkmpk.css';
import '../../css/s/sux_alb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gav8xkmpk"/><path class="sux_alb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:burger-20" {...props}></Icon>
