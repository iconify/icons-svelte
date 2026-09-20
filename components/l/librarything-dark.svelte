<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gity0fb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gity0fb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librarything-dark" {...props}></Icon>
