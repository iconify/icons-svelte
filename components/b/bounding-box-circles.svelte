<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpfw_zbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jpfw_zbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bounding-box-circles" {...props}></Icon>
