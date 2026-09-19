<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4xm4bbzh.css';
import '../../css/i/im3qhl2-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w4xm4bbzh"/><path class="im3qhl2-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:product" {...props}></Icon>
