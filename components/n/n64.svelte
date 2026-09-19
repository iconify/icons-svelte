<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy32ckbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy32ckbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:n64" {...props}></Icon>
