<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbowzx8sg.css';
import '../../css/u/ue40k2bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbowzx8sg"/><path class="ue40k2bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bell-minus-filled" {...props}></Icon>
