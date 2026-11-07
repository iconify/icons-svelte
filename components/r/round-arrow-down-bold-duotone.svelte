<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpv5vhdla.css';
import '../../css/t/tpf4ahbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="tpf4ahbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-down-bold-duotone" {...props}></Icon>
