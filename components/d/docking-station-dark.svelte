<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw5kvob9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bw5kvob9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docking-station-dark" {...props}></Icon>
