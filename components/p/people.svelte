<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iioj3obui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iioj3obui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:people" {...props}></Icon>
