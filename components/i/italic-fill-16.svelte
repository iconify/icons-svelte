<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf8o0cciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nf8o0cciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:italic-fill-16" {...props}></Icon>
