<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xluqg_7ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xluqg_7ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:google-fill" {...props}></Icon>
