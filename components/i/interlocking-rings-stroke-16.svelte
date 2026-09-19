<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgv36mbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zgv36mbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:interlocking-rings-stroke-16" {...props}></Icon>
