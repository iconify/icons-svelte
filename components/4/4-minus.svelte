<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1tx1rb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g1tx1rb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:4-minus" {...props}></Icon>
