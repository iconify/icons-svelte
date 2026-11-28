<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br0ven8-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="br0ven8-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:postage-stamp-light" {...props}></Icon>
