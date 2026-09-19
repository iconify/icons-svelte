<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3pyio9mi.css';
import '../../css/s/s9qx38vbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3pyio9mi"/><path class="s9qx38vbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:registered" {...props}></Icon>
