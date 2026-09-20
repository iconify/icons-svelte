<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv8q38bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv8q38bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-robot-confused" {...props}></Icon>
