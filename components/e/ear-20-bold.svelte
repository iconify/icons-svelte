<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1xrsabpz.css';
import '../../css/u/ug018k_ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t1xrsabpz"/><path class="ug018k_ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ear-20-bold" {...props}></Icon>
