<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ini-ntv5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ini-ntv5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:bluetooth-b" {...props}></Icon>
