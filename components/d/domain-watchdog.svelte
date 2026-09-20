<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/albryfbqk.css';
import '../../css/g/g0ke4nyhw.css';
import '../../css/r/rp0c_5bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="albryfbqk"/><path class="g0ke4nyhw"/><path class="rp0c_5bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-watchdog" {...props}></Icon>
