<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzncdpg-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xzncdpg-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pigallery2-light" {...props}></Icon>
