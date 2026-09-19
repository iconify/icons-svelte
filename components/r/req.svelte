<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr-egnj3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sr-egnj3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:req" {...props}></Icon>
