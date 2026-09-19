<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uitlmqh0r.css';
import '../../css/g/g_oiv7bye.css';
import '../../css/q/qexqi5bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uitlmqh0r"/><path class="g_oiv7bye"/><circle class="qexqi5bar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camera-tripod" {...props}></Icon>
