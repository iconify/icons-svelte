<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxe01ac_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="gxe01ac_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:palette" {...props}></Icon>
