<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp43ed8br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp43ed8br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:graph-pie-outline" {...props}></Icon>
