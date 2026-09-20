<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykq2q8kya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykq2q8kya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:planet-arrow-left" {...props}></Icon>
