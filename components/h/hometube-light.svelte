<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0j5u4hpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h0j5u4hpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hometube-light" {...props}></Icon>
