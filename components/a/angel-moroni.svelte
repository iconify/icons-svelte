<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxnef4b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nxnef4b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:angel-moroni" {...props}></Icon>
