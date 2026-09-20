<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r43chccsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r43chccsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-slider-2-outline" {...props}></Icon>
