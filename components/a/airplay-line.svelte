<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f92d32byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f92d32byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airplay-line" {...props}></Icon>
