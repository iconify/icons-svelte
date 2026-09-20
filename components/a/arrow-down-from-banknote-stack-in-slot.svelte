<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz9ab3bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wz9ab3bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-from-banknote-stack-in-slot" {...props}></Icon>
