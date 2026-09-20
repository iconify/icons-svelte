<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs4b65bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs4b65bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:music-note-off" {...props}></Icon>
