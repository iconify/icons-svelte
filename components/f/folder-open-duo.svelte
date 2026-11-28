<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wok991bpz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mi-am0x6o.css';
import '../../css/o/oy8cx5bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wok991bpz"/><g class="dt0cm9dhy primary"><path class="mi-am0x6o"/><path class="oy8cx5bvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-open-duo" {...props}></Icon>
