<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx5d-4rvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sx5d-4rvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-navigation-menu-1" {...props}></Icon>
