<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxyj6fwnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxyj6fwnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omada" {...props}></Icon>
