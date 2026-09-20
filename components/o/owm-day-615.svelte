<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqj779b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="oqj779b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-day-615" {...props}></Icon>
