<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yltwzsuot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yltwzsuot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bluetooth" {...props}></Icon>
