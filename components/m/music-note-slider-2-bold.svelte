<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c525xyy-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c525xyy-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-slider-2-bold" {...props}></Icon>
