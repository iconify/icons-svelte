<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rem61xbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rem61xbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:move" {...props}></Icon>
