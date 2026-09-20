<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj3rtbc3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gj3rtbc3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:removarr-light" {...props}></Icon>
