<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylb47iyak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ylb47iyak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:back-to-window" {...props}></Icon>
