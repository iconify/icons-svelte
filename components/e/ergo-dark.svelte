<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xny50ibfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xny50ibfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ergo-dark" {...props}></Icon>
