<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwh_5cbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwh_5cbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-close-corner-round" {...props}></Icon>
