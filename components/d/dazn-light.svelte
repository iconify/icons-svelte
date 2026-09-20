<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9-7hdctm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9-7hdctm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dazn-light" {...props}></Icon>
