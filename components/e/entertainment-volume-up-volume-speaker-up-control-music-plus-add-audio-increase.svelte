<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_xknqb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="d_xknqb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-volume-up-volume-speaker-up-control-music-plus-add-audio-increase" {...props}></Icon>
