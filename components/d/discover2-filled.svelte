<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztg_pfb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztg_pfb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:discover2-filled" {...props}></Icon>
