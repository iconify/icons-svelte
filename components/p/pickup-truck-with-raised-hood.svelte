<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkn6dvbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nkn6dvbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-with-raised-hood" {...props}></Icon>
