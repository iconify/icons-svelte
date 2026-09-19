<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvijoab-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wvijoab-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drag-vertical" {...props}></Icon>
