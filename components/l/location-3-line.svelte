<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo276fipa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo276fipa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:location-3-line" {...props}></Icon>
