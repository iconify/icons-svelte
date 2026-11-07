<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpv5vhdla.css';
import '../../css/e/epahso09d.css';
import '../../css/t/tzfojlecs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="epahso09d"/><path class="tzfojlecs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:info-circle-bold-duotone" {...props}></Icon>
