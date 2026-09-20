<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmo_ecbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fmo_ecbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-navigation-menu-3" {...props}></Icon>
