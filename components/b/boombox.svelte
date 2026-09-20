<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz47rj2ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz47rj2ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:boombox" {...props}></Icon>
