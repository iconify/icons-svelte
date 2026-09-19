<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpkmfgbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpkmfgbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-video-01" {...props}></Icon>
