<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9wlxgsem.css';
import '../../css/q/qj8o2tblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9wlxgsem"/><path class="qj8o2tblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows-forge-light" {...props}></Icon>
