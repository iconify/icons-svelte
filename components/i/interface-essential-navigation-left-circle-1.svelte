<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3lxiyb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j3lxiyb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-navigation-left-circle-1" {...props}></Icon>
