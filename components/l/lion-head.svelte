<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/aozp2s1mk.css';
import '../../css/e/ewbtvpc_j.css';
import '../../css/w/w9p-5cc-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="aozp2s1mk"/><path class="ewbtvpc_j wm-a"/><path class="w9p-5cc-x wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lion-head" {...props}></Icon>
