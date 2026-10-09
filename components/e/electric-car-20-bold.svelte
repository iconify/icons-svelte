<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6ltpbg0v.css';
import '../../css/t/t_7rprl1m.css';
import '../../css/k/ketn0_oyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g6ltpbg0v"/><path class="t_7rprl1m"/><path class="ketn0_oyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-20-bold" {...props}></Icon>
