<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh4aqo1ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":702};
const content = `<path class="nh4aqo1ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:location" {...props}></Icon>
