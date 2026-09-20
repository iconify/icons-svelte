<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbgi26j-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fbgi26j-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton" {...props}></Icon>
