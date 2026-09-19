<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdy4kbc9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdy4kbc9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ble-mesh" {...props}></Icon>
