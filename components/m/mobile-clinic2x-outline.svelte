<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/or2ri1bom.css';
import '../../css/u/ubfreac_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="or2ri1bom"/><path clip-rule="evenodd" class="ubfreac_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mobile-clinic2x-outline" {...props}></Icon>
