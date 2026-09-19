<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waetc2bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="waetc2bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pentagon-half" {...props}></Icon>
