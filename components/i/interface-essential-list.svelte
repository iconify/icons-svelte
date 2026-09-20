<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d82zkm3mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d82zkm3mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-list" {...props}></Icon>
