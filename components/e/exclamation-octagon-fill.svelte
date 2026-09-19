<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yda77z6gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yda77z6gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:exclamation-octagon-fill" {...props}></Icon>
