<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvt-tttlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dvt-tttlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:d" {...props}></Icon>
