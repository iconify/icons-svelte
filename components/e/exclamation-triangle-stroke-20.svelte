<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj4db04ha.css';
import '../../css/x/xr7c334jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wj4db04ha"/><path class="xr7c334jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:exclamation-triangle-stroke-20" {...props}></Icon>
