<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-ccf1npc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-ccf1npc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-decrease-fill" {...props}></Icon>
