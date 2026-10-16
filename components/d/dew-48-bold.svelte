<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yotzztbdp.css';
import '../../css/r/rwd6-lkjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yotzztbdp"/><path class="rwd6-lkjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dew-48-bold" {...props}></Icon>
