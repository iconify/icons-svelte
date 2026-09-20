<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iirj12wnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iirj12wnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:camera-video-remix" {...props}></Icon>
