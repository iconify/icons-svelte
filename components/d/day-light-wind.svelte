<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_2n6y2bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="g_2n6y2bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-light-wind" {...props}></Icon>
