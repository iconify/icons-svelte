<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsr7ex80b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsr7ex80b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:google-cloud" {...props}></Icon>
