<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h4fyadbly.css';
import '../../css/y/yghz7cc0o.css';
import '../../css/h/h0i813b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h4fyadbly"/><path class="yghz7cc0o"/><path clip-rule="evenodd" class="h0i813b-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-o-n-outline" {...props}></Icon>
