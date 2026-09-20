<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kurhn23aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kurhn23aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-control-button-next-button-television-buttons-movies-skip-next-video-controls" {...props}></Icon>
