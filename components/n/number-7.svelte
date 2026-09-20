<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpz2iy6dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpz2iy6dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-7" {...props}></Icon>
