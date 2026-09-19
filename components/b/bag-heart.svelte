<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0pl3acvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w0pl3acvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bag-heart" {...props}></Icon>
