<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj38i35vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xj38i35vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:excalidraw-dark" {...props}></Icon>
