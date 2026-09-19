<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/p-3d8dotc.css';
import '../../css/o/ob5x3zuiv.css';
import '../../css/b/bacrhyx6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="p-3d8dotc"/><path class="ob5x3zuiv"/><path clip-rule="evenodd" class="bacrhyx6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:adobe-indesign" {...props}></Icon>
