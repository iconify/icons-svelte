<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-hwp71hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i-hwp71hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:diesel-train-on-railway-track" {...props}></Icon>
