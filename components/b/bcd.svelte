<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av_80kbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="av_80kbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bcd" {...props}></Icon>
