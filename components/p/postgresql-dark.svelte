<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdnzp_0zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xdnzp_0zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postgresql-dark" {...props}></Icon>
