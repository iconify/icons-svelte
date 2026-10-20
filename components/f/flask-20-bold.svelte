<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkj27_b_o.css';
import '../../css/y/yhsrnr9wa.css';
import '../../css/w/w-lq_-7kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vkj27_b_o"/><path class="yhsrnr9wa"/><path class="w-lq_-7kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flask-20-bold" {...props}></Icon>
