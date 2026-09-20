<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsk0oibtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsk0oibtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:calendar-check-line" {...props}></Icon>
