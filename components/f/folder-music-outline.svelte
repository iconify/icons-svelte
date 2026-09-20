<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5-in9b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5-in9b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-music-outline" {...props}></Icon>
