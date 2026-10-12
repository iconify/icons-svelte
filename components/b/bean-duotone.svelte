<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/psh_g_bzq.css';
import '../../css/g/g08jmodsg.css';
import '../../css/u/u7ubrjgxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="psh_g_bzq"/><path class="g08jmodsg"/><path class="u7ubrjgxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bean-duotone" {...props}></Icon>
