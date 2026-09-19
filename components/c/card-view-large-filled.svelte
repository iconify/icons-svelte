<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrt9xcbpr.css';
import '../../css/x/xtmnjwu4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="wrt9xcbpr"/><path class="xtmnjwu4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:card-view-large-filled" {...props}></Icon>
