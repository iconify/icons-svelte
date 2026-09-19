<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm1c3abgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="xm1c3abgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:controlpanelalt" {...props}></Icon>
