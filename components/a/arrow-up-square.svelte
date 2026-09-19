<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5ekv3_nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g5ekv3_nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-square" {...props}></Icon>
