<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxkc8ib1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="hxkc8ib1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-804" {...props}></Icon>
