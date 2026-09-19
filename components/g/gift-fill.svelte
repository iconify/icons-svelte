<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rym_yu0mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rym_yu0mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:gift-fill" {...props}></Icon>
