<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogkmfrk0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ogkmfrk0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-alt-circle-up" {...props}></Icon>
