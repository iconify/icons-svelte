<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vof1wyoxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vof1wyoxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lovart" {...props}></Icon>
