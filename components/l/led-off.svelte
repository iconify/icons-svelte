<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzb-k98lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzb-k98lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:led-off" {...props}></Icon>
