<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0i-0-khj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i0i-0-khj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:cart" {...props}></Icon>
