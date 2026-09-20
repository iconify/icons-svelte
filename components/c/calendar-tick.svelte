<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us4gtfhsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us4gtfhsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-tick" {...props}></Icon>
