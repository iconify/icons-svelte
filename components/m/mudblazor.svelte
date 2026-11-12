<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxvuarbsa.css';
import '../../css/y/yaky7tbun.css';
import '../../css/g/gj4t4ybgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1404,"height":1404};
const content = `<path class="nxvuarbsa"/><path class="yaky7tbun"/><path class="gj4t4ybgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mudblazor" {...props}></Icon>
