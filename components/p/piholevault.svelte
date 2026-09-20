<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixcjahbeg.css';
import '../../css/v/v3ts8bbtq.css';
import '../../css/c/cspszkbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ixcjahbeg"/><path class="v3ts8bbtq"/><path class="cspszkbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piholevault" {...props}></Icon>
