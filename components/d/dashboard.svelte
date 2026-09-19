<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv5t7cb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":456};
const content = `<path class="yv5t7cb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dashboard" {...props}></Icon>
