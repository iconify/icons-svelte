<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx2i2kbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx2i2kbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layer-bring-forward" {...props}></Icon>
