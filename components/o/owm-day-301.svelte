<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frrqm0b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="frrqm0b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-day-301" {...props}></Icon>
