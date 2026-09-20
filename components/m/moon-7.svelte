<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic8wy5bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ic8wy5bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-7" {...props}></Icon>
