<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtwmk_nhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtwmk_nhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nursing-home" {...props}></Icon>
