<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s31oqeb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s31oqeb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:house-with-flag" {...props}></Icon>
