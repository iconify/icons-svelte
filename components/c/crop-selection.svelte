<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me5ba80yv.css';
import '../../css/i/iyb1cbc4d.css';
import '../../css/f/ffscyns8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="me5ba80yv"><path class="iyb1cbc4d"/><path class="ffscyns8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:crop-selection" {...props}></Icon>
