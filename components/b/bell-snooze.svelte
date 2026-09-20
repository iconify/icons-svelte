<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/w/w8dd_zm0v.css';
import '../../css/p/p5w2crbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="w8dd_zm0v"/><path class="p5w2crbbm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:bell-snooze" {...props}></Icon>
