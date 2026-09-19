<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7dld0b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i7dld0b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:messenger-stroke-16" {...props}></Icon>
