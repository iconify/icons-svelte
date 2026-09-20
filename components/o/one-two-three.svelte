<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr9h2wbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dr9h2wbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:one-two-three" {...props}></Icon>
