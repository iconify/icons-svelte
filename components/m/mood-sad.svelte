<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unt32jbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unt32jbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mood-sad" {...props}></Icon>
