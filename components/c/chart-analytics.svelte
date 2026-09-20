<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p07tmccvv.css';
import '../../css/d/d4oe1undt.css';
import '../../css/k/k3nbxy6lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="d4oe1undt"/><path class="k3nbxy6lf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-analytics" {...props}></Icon>
