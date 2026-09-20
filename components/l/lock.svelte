<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq14ewv-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zq14ewv-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:lock" {...props}></Icon>
