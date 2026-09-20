<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj39dlnoc.css';
import '../../css/w/wfdwuhjle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bj39dlnoc"/><path class="wfdwuhjle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-keyboard" {...props}></Icon>
