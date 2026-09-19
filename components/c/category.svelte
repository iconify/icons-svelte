<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgn19vb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":551,"height":717};
const content = `<path class="rgn19vb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:category" {...props}></Icon>
