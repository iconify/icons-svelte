<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlzpevisc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlzpevisc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:roblox-line" {...props}></Icon>
