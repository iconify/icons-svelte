<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-2wu0c7s.css';
import '../../css/k/ksujj2ycj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y-2wu0c7s"/><path class="ksujj2ycj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:event-incident" {...props}></Icon>
