<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsr46tb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsr46tb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eyedropper-off" {...props}></Icon>
