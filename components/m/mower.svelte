<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiqll0z-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiqll0z-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mower" {...props}></Icon>
