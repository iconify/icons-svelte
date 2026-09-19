<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwrczlbqy.css';
import '../../css/g/g-8u0m53a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rwrczlbqy"/><path class="g-8u0m53a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-monitoring" {...props}></Icon>
