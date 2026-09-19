<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f35lyobeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="f35lyobeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alignleftedge" {...props}></Icon>
