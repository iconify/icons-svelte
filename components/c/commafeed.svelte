<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scv3-lbfi.css';
import '../../css/z/zlknd4b1p.css';
import '../../css/o/o6k9xwbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6.563,"height":6.563};
const content = `<rect class="scv3-lbfi"/><path class="zlknd4b1p"/><path class="o6k9xwbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:commafeed" {...props}></Icon>
