<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jryms8byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jryms8byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:dash-stroke-16" {...props}></Icon>
