<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh9mglbwk.css';
import '../../css/m/mdt1zbc6x.css';
import '../../css/h/hnvcyqpyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qh9mglbwk"/><path class="mdt1zbc6x"/><path class="hnvcyqpyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-recording-outline" {...props}></Icon>
