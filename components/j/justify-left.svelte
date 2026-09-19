<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpu53juwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zpu53juwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:justify-left" {...props}></Icon>
