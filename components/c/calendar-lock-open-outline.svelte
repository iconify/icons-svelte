<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu97ff9zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu97ff9zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-lock-open-outline" {...props}></Icon>
