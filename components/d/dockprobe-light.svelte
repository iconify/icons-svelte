<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdrgw4bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdrgw4bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockprobe-light" {...props}></Icon>
