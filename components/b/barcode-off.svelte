<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xodp15i4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xodp15i4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:barcode-off" {...props}></Icon>
