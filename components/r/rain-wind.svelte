<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4yvbibxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="q4yvbibxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:rain-wind" {...props}></Icon>
