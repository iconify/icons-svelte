<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-c7k_big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i-c7k_big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:cloud" {...props}></Icon>
