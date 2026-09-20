<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi7fw_q4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi7fw_q4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-number-9-filled" {...props}></Icon>
