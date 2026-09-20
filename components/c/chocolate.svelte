<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oimfb3b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oimfb3b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chocolate" {...props}></Icon>
