<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz69eqhxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz69eqhxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-weekend" {...props}></Icon>
