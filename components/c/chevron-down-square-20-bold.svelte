<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fec4cjbkq.css';
import '../../css/q/qcaq4pnjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fec4cjbkq"/><path class="qcaq4pnjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-down-square-20-bold" {...props}></Icon>
