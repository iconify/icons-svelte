<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbkzq4bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbkzq4bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-collapse-horizontal-outline" {...props}></Icon>
