<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drqu0h0xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drqu0h0xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fill" {...props}></Icon>
