<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrlbef4-h.css';
import '../../css/y/y17nwib9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yrlbef4-h"/><path class="y17nwib9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-click-select-tablet" {...props}></Icon>
