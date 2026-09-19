<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2r3iofuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v2r3iofuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:original-size-stroke-16" {...props}></Icon>
