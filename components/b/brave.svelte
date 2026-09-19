<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orl20abyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="orl20abyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:brave" {...props}></Icon>
