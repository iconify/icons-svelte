<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0f0lbbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0f0lbbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-weeks" {...props}></Icon>
