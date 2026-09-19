<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd64d3bvp.css';
import '../../css/b/blynalbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fd64d3bvp"/><rect class="blynalbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lock-unlocked-fill-16" {...props}></Icon>
