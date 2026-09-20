<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpp5505dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpp5505dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fog-night-filled" {...props}></Icon>
