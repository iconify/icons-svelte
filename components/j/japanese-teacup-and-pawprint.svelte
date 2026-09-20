<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5i_mx52w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r5i_mx52w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:japanese-teacup-and-pawprint" {...props}></Icon>
