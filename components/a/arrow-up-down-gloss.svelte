<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqozpfb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqozpfb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-up-down-gloss" {...props}></Icon>
