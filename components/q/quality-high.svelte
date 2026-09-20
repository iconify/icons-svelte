<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt96enbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt96enbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:quality-high" {...props}></Icon>
