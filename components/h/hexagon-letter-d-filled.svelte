<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhxp6ccgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhxp6ccgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-d-filled" {...props}></Icon>
