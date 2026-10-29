<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hw5l17qef.css';
import '../../css/k/kgvwdybzv.css';
import '../../css/p/pr4hfob0i.css';
import '../../css/t/t1hpgfxns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hw5l17qef"/><path class="kgvwdybzv wm-a"/><path class="pr4hfob0i"/><path class="t1hpgfxns wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:luggage-duo" {...props}></Icon>
