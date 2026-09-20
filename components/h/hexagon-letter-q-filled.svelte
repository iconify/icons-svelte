<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6977s0_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6977s0_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-q-filled" {...props}></Icon>
