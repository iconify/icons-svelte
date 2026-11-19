<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv8i9sblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dv8i9sblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentodo-light" {...props}></Icon>
