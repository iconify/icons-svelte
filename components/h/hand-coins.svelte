<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/eq2iy9b8b.css';
import '../../css/b/bl-ncmb1l.css';
import '../../css/q/qaarkib0y.css';
import '../../css/y/yle7k-b8s.css';
import '../../css/m/mrwc-puoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="eq2iy9b8b"/><path class="bl-ncmb1l"/><path class="qaarkib0y"/><path class="yle7k-b8s"/><path class="mrwc-puoh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hand-coins" {...props}></Icon>
