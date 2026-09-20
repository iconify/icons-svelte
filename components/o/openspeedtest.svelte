<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo88zq3co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zo88zq3co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openspeedtest" {...props}></Icon>
