<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxy2vycti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxy2vycti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:globe-off-fill-round" {...props}></Icon>
