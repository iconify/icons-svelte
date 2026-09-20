<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c35gnuhtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="c35gnuhtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-day-721" {...props}></Icon>
