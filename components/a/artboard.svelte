<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld2p2fbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld2p2fbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:artboard" {...props}></Icon>
