<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9iqw6b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z9iqw6b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-greek-cross" {...props}></Icon>
