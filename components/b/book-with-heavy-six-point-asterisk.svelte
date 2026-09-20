<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnj1zubho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fnj1zubho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-heavy-six-point-asterisk" {...props}></Icon>
