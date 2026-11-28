<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt04mfb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wt04mfb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:magnifying-glass-x" {...props}></Icon>
