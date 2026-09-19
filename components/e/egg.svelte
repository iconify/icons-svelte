<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvwdo60w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wwvwdo60w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:egg" {...props}></Icon>
