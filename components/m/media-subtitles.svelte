<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oysdye0wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oysdye0wl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-subtitles" {...props}></Icon>
