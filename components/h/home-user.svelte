<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q30_42vkc.css';
import '../../css/d/dubamxw4b.css';
import '../../css/p/pfa780btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q30_42vkc"/><path class="dubamxw4b"/><path class="pfa780btb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:home-user" {...props}></Icon>
