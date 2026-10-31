<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik3-pabpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik3-pabpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lightbulb-gloss" {...props}></Icon>
