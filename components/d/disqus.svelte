<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjn9m-sfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":416};
const content = `<path class="rjn9m-sfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:disqus" {...props}></Icon>
