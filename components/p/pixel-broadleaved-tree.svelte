<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nss30vccu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nss30vccu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-broadleaved-tree" {...props}></Icon>
