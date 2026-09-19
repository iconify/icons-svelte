<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn5ynfb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dn5ynfb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cheese" {...props}></Icon>
