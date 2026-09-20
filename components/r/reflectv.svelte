<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuw0fpp4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zuw0fpp4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:reflectv" {...props}></Icon>
