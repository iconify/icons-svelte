<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbtsv3bus.css';
import '../../css/g/gtqcty8ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vbtsv3bus"/><path class="gtqcty8ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-video-movie-producer-director-chair" {...props}></Icon>
