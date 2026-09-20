<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfg6--vbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfg6--vbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:laurel-wreath-3-filled" {...props}></Icon>
