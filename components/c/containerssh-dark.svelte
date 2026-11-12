<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhjv5acyx.css';
import '../../css/v/vu03pvbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fhjv5acyx"/><path class="vu03pvbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:containerssh-dark" {...props}></Icon>
