<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q234p0z5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q234p0z5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-rest-quarter" {...props}></Icon>
