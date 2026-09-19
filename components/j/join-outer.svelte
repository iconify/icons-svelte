<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy6cbetxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iy6cbetxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:join-outer" {...props}></Icon>
