<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i55rs9b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i55rs9b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pleroma-light" {...props}></Icon>
