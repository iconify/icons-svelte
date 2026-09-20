<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3vbln6xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w3vbln6xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:crane-portal" {...props}></Icon>
