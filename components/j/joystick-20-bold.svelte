<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp7d7nb3s.css';
import '../../css/v/vqqrrtxdj.css';
import '../../css/a/a0erdxoze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lp7d7nb3s"/><path class="vqqrrtxdj"/><path class="a0erdxoze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:joystick-20-bold" {...props}></Icon>
