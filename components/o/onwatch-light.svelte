<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar-w1rbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ar-w1rbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onwatch-light" {...props}></Icon>
