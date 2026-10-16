<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqu2_e4mu.css';
import '../../css/x/xqvmvkbpa.css';
import '../../css/g/g-eromb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g transform="matrix(1 0 0 -1 0 512)"><circle class="pqu2_e4mu"/><path class="xqvmvkbpa"/><path class="g-eromb9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:redlib" {...props}></Icon>
