<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b819-vbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b819-vbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-speed-limiter" {...props}></Icon>
