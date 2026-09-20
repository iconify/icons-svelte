<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gae81t6qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gae81t6qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nforwardauth-light" {...props}></Icon>
