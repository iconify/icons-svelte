<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg79iebtx.css';
import '../../css/p/pnj4y1nku.css';
import '../../css/y/ybgg7vk0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fg79iebtx"/><path class="pnj4y1nku"/><path class="ybgg7vk0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:monster" {...props}></Icon>
