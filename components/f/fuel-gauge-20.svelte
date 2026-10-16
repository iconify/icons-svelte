<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d03rjttsh.css';
import '../../css/x/x4s1haczx.css';
import '../../css/f/fi3lb_64h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d03rjttsh"/><path class="x4s1haczx"/><path class="fi3lb_64h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-gauge-20" {...props}></Icon>
