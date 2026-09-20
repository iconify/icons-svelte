<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-qgs2bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-qgs2bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:remote-tv-off" {...props}></Icon>
