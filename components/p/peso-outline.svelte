<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x-8ter4yn.css';
import '../../css/d/dndb2vpww.css';
import '../../css/b/b9udazptr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="x-8ter4yn"/><path clip-rule="evenodd" class="dndb2vpww"/><path class="b9udazptr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:peso-outline" {...props}></Icon>
