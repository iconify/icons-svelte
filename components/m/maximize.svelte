<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imv2uwbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imv2uwbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:maximize" {...props}></Icon>
