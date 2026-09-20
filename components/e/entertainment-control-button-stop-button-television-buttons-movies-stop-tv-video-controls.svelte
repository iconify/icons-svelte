<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmyrtdb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<rect class="mmyrtdb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-control-button-stop-button-television-buttons-movies-stop-tv-video-controls" {...props}></Icon>
