<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/s7qxfdbrb.css';
import '../../css/h/hwsal5q-o.css';
import '../../css/z/ze6eu2fom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="s7qxfdbrb"/><circle class="hwsal5q-o"/><path class="ze6eu2fom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:hand-brake" {...props}></Icon>
