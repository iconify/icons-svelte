<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmx57fb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cmx57fb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-richtext-fill" {...props}></Icon>
