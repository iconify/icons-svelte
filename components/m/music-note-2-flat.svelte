<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp9mcwqrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vp9mcwqrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:music-note-2-flat" {...props}></Icon>
