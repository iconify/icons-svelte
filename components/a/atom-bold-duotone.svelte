<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vack09bmc.css';
import '../../css/z/zno_he9df.css';
import '../../css/m/mxe9l_zuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vack09bmc"/><path class="zno_he9df"/><path class="mxe9l_zuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:atom-bold-duotone" {...props}></Icon>
