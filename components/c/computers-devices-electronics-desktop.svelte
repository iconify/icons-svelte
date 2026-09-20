<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3e1967if.css';
import '../../css/f/f9s06tb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c3e1967if"/><path class="f9s06tb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-desktop" {...props}></Icon>
