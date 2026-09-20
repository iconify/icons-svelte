<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl-bsbz7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="rl-bsbz7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-18" {...props}></Icon>
