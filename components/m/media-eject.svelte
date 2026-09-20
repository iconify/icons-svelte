<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9pq_3bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9pq_3bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-eject" {...props}></Icon>
