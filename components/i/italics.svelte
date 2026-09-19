<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0hsrcwic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i0hsrcwic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:italics" {...props}></Icon>
