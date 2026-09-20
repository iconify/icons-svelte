<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9wl3ibck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j9wl3ibck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:direction" {...props}></Icon>
