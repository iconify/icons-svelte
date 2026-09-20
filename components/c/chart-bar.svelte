<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wws2w5bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wws2w5bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chart-bar" {...props}></Icon>
