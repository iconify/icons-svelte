<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-bh2obll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m-bh2obll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-image-fill-16" {...props}></Icon>
