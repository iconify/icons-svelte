<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3vxfob2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":392};
const content = `<path class="g3vxfob2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:refresh-sync-disabled" {...props}></Icon>
