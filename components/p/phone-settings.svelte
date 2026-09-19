<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfddwd_7g.css';
import '../../css/j/j0j3yqboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yfddwd_7g"/><path class="j0j3yqboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:phone-settings" {...props}></Icon>
