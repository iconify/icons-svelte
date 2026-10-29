<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o0lv7fb0z.css';
import '../../css/i/ibvzxbc8p.css';
import '../../css/x/x-m_43jif.css';
import '../../css/u/urjdred5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o0lv7fb0z"/><path class="ibvzxbc8p wm-a"/><path class="x-m_43jif"/><path class="urjdred5d wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pickaxe-duo" {...props}></Icon>
