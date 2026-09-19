<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/ira41xb9p.css';
import '../../css/h/hwsal5q-o.css';
import '../../css/p/pljtn-4ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><ellipse class="ira41xb9p"/><circle class="hwsal5q-o"/><path class="pljtn-4ly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:globe-outline" {...props}></Icon>
