<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_cq7wdxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_cq7wdxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-wirelessbutton" {...props}></Icon>
