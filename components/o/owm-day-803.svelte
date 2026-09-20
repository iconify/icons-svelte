<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xidxtptqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="xidxtptqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-day-803" {...props}></Icon>
