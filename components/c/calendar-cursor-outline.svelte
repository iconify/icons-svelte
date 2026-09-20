<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k76wz3z4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k76wz3z4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-cursor-outline" {...props}></Icon>
