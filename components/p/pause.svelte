<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh0aorlcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bh0aorlcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:pause" {...props}></Icon>
