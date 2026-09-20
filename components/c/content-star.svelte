<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hglly4p7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hglly4p7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-star" {...props}></Icon>
