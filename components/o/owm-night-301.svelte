<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr_iggcno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="gr_iggcno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-301" {...props}></Icon>
