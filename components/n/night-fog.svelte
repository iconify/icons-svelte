<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uorq20b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="uorq20b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-fog" {...props}></Icon>
