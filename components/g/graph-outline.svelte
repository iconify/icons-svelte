<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdz3jzvqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdz3jzvqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:graph-outline" {...props}></Icon>
