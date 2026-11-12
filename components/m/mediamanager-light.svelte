<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkff-3cxp.css';
import '../../css/z/z6tzkqpon.css';
import '../../css/v/vcnt0ibmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkff-3cxp"/><path class="z6tzkqpon"/><path class="vcnt0ibmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamanager-light" {...props}></Icon>
