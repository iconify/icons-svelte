<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by0_zkbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="by0_zkbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:corner-bottom-right" {...props}></Icon>
