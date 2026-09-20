<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4_xreixv.css';
import '../../css/t/te4hkcb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4_xreixv"/><path class="te4hkcb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-moved-24" {...props}></Icon>
