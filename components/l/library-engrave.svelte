<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y576glb9g.css';
import '../../css/a/ajdr2dz1w.css';
import '../../css/z/z30wqlwgo.css';
import '../../css/l/lskjy3bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y576glb9g"/><path class="ajdr2dz1w wm-a"/><path class="wm-shadow z30wqlwgo"/><path class="lskjy3bhz wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:library-engrave" {...props}></Icon>
