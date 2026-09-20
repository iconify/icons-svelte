<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6wx27b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y6wx27b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:media" {...props}></Icon>
