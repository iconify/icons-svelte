<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuz937pqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuz937pqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:animation-play" {...props}></Icon>
