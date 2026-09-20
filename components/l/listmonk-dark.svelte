<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgew44bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wgew44bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listmonk-dark" {...props}></Icon>
