<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrcma3buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mrcma3buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-left" {...props}></Icon>
