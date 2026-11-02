<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vacz3xbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vacz3xbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-fold-line" {...props}></Icon>
