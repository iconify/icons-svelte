<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrk_2ibne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrk_2ibne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-scatter-fill-round" {...props}></Icon>
