<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar0xbeyhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar0xbeyhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:output" {...props}></Icon>
