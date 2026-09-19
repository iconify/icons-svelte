<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brjxukbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="brjxukbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-download-fill" {...props}></Icon>
