<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbt65ccmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbt65ccmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gas-station-line" {...props}></Icon>
