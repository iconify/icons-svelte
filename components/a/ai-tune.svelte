<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k9x5ajbdu.css';
import '../../css/a/a-fj8301e.css';
import '../../css/r/rbx21knaf.css';
import '../../css/f/f-4a3gumk.css';
import '../../css/q/qgoj2cb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k9x5ajbdu"/><circle class="a-fj8301e"/><path class="rbx21knaf"/><circle class="f-4a3gumk"/><path class="qgoj2cb0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-tune" {...props}></Icon>
