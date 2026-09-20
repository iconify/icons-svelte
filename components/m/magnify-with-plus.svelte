<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgu8e5b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fgu8e5b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:magnify-with-plus" {...props}></Icon>
