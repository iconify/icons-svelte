<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot-zu_b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot-zu_b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:changing-room-hanger" {...props}></Icon>
