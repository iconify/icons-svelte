<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm3rfcb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wm3rfcb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:observation-tower" {...props}></Icon>
