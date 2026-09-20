<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnx33c0jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fnx33c0jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:line-spacing" {...props}></Icon>
