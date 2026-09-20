<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0_wgyb4o.css';
import '../../css/t/tpvreibwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":268};
const content = `<path class="m0_wgyb4o"/><path class="tpvreibwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:notion" {...props}></Icon>
