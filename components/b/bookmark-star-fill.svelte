<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4-fsjbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v4-fsjbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bookmark-star-fill" {...props}></Icon>
