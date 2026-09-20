<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyeser1ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dyeser1ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-rupee" {...props}></Icon>
