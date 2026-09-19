<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxzi1obna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="mxzi1obna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:flickr" {...props}></Icon>
