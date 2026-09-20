<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj-4iw7vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj-4iw7vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-off" {...props}></Icon>
