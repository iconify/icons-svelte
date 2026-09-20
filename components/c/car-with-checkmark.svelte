<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdkdccu0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zdkdccu0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-checkmark" {...props}></Icon>
