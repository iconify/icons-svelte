<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_tkm_8we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k_tkm_8we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cairn-and-three-tall-rectangles-right" {...props}></Icon>
