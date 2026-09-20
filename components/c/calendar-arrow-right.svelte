<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xijjq8bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xijjq8bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-arrow-right" {...props}></Icon>
