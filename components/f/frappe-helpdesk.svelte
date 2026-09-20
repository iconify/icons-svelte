<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbmsbj1ug.css';
import '../../css/m/m0hpcl8zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbmsbj1ug"/><path class="m0hpcl8zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-helpdesk" {...props}></Icon>
