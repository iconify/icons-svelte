<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-m5ubxc.css';
import '../../css/d/dn1u2whmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-m5ubxc"/><path class="dn1u2whmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bone-crack-bold-duotone" {...props}></Icon>
