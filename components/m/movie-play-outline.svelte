<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uurj7xe-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uurj7xe-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-play-outline" {...props}></Icon>
