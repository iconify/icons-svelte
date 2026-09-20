<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8bw_lb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n8bw_lb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:ethernet" {...props}></Icon>
