<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynezi9bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynezi9bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-refresh" {...props}></Icon>
