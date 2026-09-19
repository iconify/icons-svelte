<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y0qazqbcv.css';
import '../../css/k/k3dstcbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y0qazqbcv"/><path class="k3dstcbyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:facebook-one" {...props}></Icon>
