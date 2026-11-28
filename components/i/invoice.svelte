<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v-1ltacmn.css';
import '../../css/p/potl1vbrd.css';
import '../../css/d/dxc5lhiyx.css';
import '../../css/k/kerqeobiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="v-1ltacmn"/><path class="potl1vbrd"/><path class="dxc5lhiyx"/><path class="kerqeobiq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:invoice" {...props}></Icon>
