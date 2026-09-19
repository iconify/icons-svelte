<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv88xp9pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":456};
const content = `<path class="zv88xp9pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-roll" {...props}></Icon>
