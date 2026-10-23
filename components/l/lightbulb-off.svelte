<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvxwe742c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvxwe742c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:lightbulb-off" {...props}></Icon>
