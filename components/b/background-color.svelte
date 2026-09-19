<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-6w6s5mn.css';
import '../../css/z/zpv0px87x.css';
import '../../css/h/hvoz6u48w.css';
import '../../css/g/gzz6--gdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f-6w6s5mn"/><path class="zpv0px87x"/><path class="hvoz6u48w"/><path class="gzz6--gdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:background-color" {...props}></Icon>
