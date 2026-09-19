<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm5cl11de.css';
import '../../css/c/cc7ygfb5j.css';
import '../../css/l/ljikcn5lw.css';
import '../../css/d/dz18mgexq.css';
import '../../css/g/gnxoapbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="xm5cl11de"><path class="cc7ygfb5j"/><path class="ljikcn5lw"/><path class="dz18mgexq"/><path class="gnxoapbgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:postcss" {...props}></Icon>
