<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvj_-bb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kvj_-bb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-video-games" {...props}></Icon>
