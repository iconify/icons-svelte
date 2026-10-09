<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvmh4mb4l.css';
import '../../css/s/s0fmfdclg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mvmh4mb4l"/><path class="s0fmfdclg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-price-20" {...props}></Icon>
