<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8vo2-1qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8vo2-1qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-heart-outline" {...props}></Icon>
