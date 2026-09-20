<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b8z23pe4m.css';
import '../../css/j/j6nfug34l.css';
import '../../css/v/v2h-64b7s.css';
import '../../css/h/h0y1y9b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b8z23pe4m"/><path class="j6nfug34l"/><path class="v2h-64b7s"/><path class="h0y1y9b6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:play-demo" {...props}></Icon>
