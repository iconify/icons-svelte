<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5y3i_byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5y3i_byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:calendar-exclamation" {...props}></Icon>
