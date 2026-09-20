<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nosv9sbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nosv9sbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-day" {...props}></Icon>
