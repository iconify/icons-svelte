<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8befvb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c8befvb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bag-with-greek-cross" {...props}></Icon>
