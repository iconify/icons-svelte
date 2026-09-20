<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4-bqjb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4-bqjb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arcane" {...props}></Icon>
