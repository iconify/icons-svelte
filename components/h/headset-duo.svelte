<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c4haflbwb.css';
import '../../css/c/cvk-bup-z.css';
import '../../css/i/iatj5le9x.css';
import '../../css/j/j2t9-upmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="c4haflbwb"/><path class="cvk-bup-z wm-a"/><path class="iatj5le9x"/><path class="j2t9-upmx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:headset-duo" {...props}></Icon>
