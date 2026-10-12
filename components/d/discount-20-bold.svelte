<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm5j5xizl.css';
import '../../css/k/kbq43k7wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wm5j5xizl"/><path class="kbq43k7wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:discount-20-bold" {...props}></Icon>
