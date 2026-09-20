<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv_-1uxed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tv_-1uxed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:laudspeaker-light" {...props}></Icon>
