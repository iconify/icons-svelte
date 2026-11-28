<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7a_usb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7a_usb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:podium" {...props}></Icon>
