<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtm_h7umf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtm_h7umf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:game-1-line" {...props}></Icon>
