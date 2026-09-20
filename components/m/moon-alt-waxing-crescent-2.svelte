<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-uxu8b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="t-uxu8b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waxing-crescent-2" {...props}></Icon>
