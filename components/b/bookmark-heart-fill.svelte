<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti-29ubjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ti-29ubjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bookmark-heart-fill" {...props}></Icon>
