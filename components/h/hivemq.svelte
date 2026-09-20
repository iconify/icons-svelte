<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbxra6t0y.css';
import '../../css/s/sm4k7rbaa.css';
import '../../css/m/mg66m1bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbxra6t0y"/><path class="sm4k7rbaa"/><path class="mg66m1bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hivemq" {...props}></Icon>
