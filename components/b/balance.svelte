<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vss48e-1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":456};
const content = `<path class="vss48e-1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:balance" {...props}></Icon>
