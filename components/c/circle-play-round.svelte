<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy89lmqks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy89lmqks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-play-round" {...props}></Icon>
