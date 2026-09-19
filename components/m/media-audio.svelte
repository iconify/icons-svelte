<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9go9ysuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a9go9ysuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:media-audio" {...props}></Icon>
