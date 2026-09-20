<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnwa2-bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnwa2-bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-l-box" {...props}></Icon>
