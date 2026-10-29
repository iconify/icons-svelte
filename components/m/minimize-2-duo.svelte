<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f_o9585tx.css';
import '../../css/z/z_leajngu.css';
import '../../css/j/j7ffi82vm.css';
import '../../css/n/nz03h8bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f_o9585tx"/><path class="wm-a z_leajngu"/><path class="j7ffi82vm"/><path class="nz03h8bkr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minimize-2-duo" {...props}></Icon>
