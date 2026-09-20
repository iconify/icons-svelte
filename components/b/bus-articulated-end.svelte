<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y460ngfdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y460ngfdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-articulated-end" {...props}></Icon>
