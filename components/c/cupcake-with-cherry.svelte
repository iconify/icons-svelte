<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7rz5mx2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r7rz5mx2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cupcake-with-cherry" {...props}></Icon>
