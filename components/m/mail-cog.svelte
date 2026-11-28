<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h1ma72bft.css';
import '../../css/l/llr9rqbjq.css';
import '../../css/d/dq60wlbxs.css';
import '../../css/b/b9him6jfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h1ma72bft"/><path class="llr9rqbjq"/><path class="dq60wlbxs"/><path class="b9him6jfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-cog" {...props}></Icon>
