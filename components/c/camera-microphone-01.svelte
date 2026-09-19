<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/g0pf61plc.css';
import '../../css/f/fwl6ucbbe.css';
import '../../css/b/bjxwieloe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="g0pf61plc"/><path class="fwl6ucbbe"/><path class="bjxwieloe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camera-microphone-01" {...props}></Icon>
