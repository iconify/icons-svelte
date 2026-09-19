<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyihokqvh.css';
import '../../css/y/yyovchb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gyihokqvh"/><path class="yyovchb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-right-02-filled" {...props}></Icon>
