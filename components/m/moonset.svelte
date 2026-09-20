<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7k-s0i3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="c7k-s0i3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moonset" {...props}></Icon>
