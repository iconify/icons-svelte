<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l4pfilrbr.css';
import '../../css/m/mv74flbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3.5};
const content = `<g class="cuyn6tgcc"><path class="l4pfilrbr"/><path class="mv74flbio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:amazon" {...props}></Icon>
