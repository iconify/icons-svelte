<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rf6i3943p.css';
import '../../css/o/o8ta-ebdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="rf6i3943p"/><path clip-rule="evenodd" class="o8ta-ebdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:malaria-pf-microscope" {...props}></Icon>
