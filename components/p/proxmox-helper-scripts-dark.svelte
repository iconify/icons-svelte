<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxpyyq7ha.css';
import '../../css/a/a76ci7s7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxpyyq7ha"/><path class="a76ci7s7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxmox-helper-scripts-dark" {...props}></Icon>
