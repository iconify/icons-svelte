<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0a9vkbzg.css';
import '../../css/p/pbc3tob8h.css';
import '../../css/r/rd16i8rjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="pbc3tob8h"/><path class="rd16i8rjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:graphic-design" {...props}></Icon>
