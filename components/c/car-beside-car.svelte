<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_s23zb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a_s23zb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-beside-car" {...props}></Icon>
