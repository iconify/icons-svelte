<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrwtddt_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lrwtddt_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:diaper" {...props}></Icon>
