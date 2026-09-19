<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dumv5nw4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="dumv5nw4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:cloud" {...props}></Icon>
