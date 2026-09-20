<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7wd8hbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h7wd8hbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:media-play" {...props}></Icon>
