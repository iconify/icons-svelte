<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozb6knb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozb6knb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-star-outline" {...props}></Icon>
