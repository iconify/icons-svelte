<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke40b1uoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ke40b1uoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-navigation-right-circle-1" {...props}></Icon>
