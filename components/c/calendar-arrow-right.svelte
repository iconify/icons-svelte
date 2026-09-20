<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phdf0gb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phdf0gb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-arrow-right" {...props}></Icon>
