<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvt_mub5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvt_mub5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lightbulb-off-line" {...props}></Icon>
