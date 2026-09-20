<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcc4chb-g.css';
import '../../css/g/g2v-e666n.css';
import '../../css/w/w5gr3vtml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<g class="lcc4chb-g"><path class="g2v-e666n"/><path class="w5gr3vtml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dailydotdev-light" {...props}></Icon>
