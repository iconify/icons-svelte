<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhq0jyybt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lhq0jyybt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-head-and-shoulders" {...props}></Icon>
