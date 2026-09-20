<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsbq87ajf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fsbq87ajf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:letter-spacing" {...props}></Icon>
