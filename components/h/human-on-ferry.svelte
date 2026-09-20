<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulg-h6bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ulg-h6bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:human-on-ferry" {...props}></Icon>
