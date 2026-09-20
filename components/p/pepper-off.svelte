<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf9u4htgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf9u4htgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pepper-off" {...props}></Icon>
