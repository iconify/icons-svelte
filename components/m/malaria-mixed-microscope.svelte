<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/ziuoucl8y.css';
import '../../css/h/hxfqxacle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ziuoucl8y"/><path clip-rule="evenodd" class="hxfqxacle"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:malaria-mixed-microscope" {...props}></Icon>
