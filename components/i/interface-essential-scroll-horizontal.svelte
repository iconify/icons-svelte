<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c35hgrb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c35hgrb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-scroll-horizontal" {...props}></Icon>
