<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juf828bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="juf828bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:flickr" {...props}></Icon>
