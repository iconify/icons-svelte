<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytw0m4b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ytw0m4b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-from-banknote-in-slot" {...props}></Icon>
