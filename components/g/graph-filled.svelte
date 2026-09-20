<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm6y613bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nm6y613bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:graph-filled" {...props}></Icon>
