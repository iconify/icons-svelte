<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n31ha_blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n31ha_blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:motorbike-fill-round" {...props}></Icon>
