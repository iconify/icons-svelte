<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srefg3b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="srefg3b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:p-wide-in-parking-structure" {...props}></Icon>
