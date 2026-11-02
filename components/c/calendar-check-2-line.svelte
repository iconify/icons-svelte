<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtfaehbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtfaehbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-check-2-line" {...props}></Icon>
