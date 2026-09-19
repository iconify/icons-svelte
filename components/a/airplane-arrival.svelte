<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lguui-g7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lguui-g7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:airplane-arrival" {...props}></Icon>
