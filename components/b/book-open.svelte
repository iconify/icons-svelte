<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g-hs3vbsc.css';
import '../../css/e/elyi5abmp.css';
import '../../css/i/iqliabezm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g-hs3vbsc"/><path class="elyi5abmp"/><path class="iqliabezm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:book-open" {...props}></Icon>
