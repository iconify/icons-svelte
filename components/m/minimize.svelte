<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlak9g5tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dlak9g5tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:minimize" {...props}></Icon>
