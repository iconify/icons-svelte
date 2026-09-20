<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2_atrbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="s2_atrbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-day-210" {...props}></Icon>
