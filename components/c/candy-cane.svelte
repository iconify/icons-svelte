<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5z_dxebm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g5z_dxebm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:candy-cane" {...props}></Icon>
