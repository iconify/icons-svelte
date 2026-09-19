<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf1ugp_oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf1ugp_oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mayan-pyramid" {...props}></Icon>
