<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu42zbd3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yu42zbd3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aeterna-light" {...props}></Icon>
