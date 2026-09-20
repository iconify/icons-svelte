<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj2p_abnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj2p_abnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ice-water" {...props}></Icon>
