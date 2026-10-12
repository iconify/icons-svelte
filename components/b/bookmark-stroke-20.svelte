<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_9hn1bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t_9hn1bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bookmark-stroke-20" {...props}></Icon>
