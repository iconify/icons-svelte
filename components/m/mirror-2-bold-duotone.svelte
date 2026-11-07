<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8vnt_j9i.css';
import '../../css/p/pxdv6ta5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8vnt_j9i"/><path class="pxdv6ta5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mirror-2-bold-duotone" {...props}></Icon>
