<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh2hcmbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":432};
const content = `<path class="eh2hcmbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flash-off" {...props}></Icon>
