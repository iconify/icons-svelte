<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s24s4wb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s24s4wb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rhombus-outline" {...props}></Icon>
