<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzx--cc9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rzx--cc9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pill-bottle-with-capsule-pill" {...props}></Icon>
