<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmdaz5j3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmdaz5j3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:move-to-inbox" {...props}></Icon>
