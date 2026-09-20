<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u7jin0b7z.css';
import '../../css/v/vwg43ut4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="u7jin0b7z"/><path class="ouiIcon__fillSecondary vwg43ut4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-devtools" {...props}></Icon>
