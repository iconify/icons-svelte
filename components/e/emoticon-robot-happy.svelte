<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-ckjob3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ckjob3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-robot-happy" {...props}></Icon>
