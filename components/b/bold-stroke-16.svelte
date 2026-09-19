<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx75f44uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jx75f44uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bold-stroke-16" {...props}></Icon>
