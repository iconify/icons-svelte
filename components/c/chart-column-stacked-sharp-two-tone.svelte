<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/b/beuh13b9y.css';
import '../../css/p/p53xcyb3q.css';
import '../../css/c/cfjq2zbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="beuh13b9y"/><path class="p53xcyb3q"/><path class="cfjq2zbua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-column-stacked-sharp-two-tone" {...props}></Icon>
