<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur913e2io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ur913e2io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mixpost-dark" {...props}></Icon>
