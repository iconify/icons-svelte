<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxjghm4yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kxjghm4yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:computer-laptop" {...props}></Icon>
