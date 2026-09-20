<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oua8-7eug.css';
import '../../css/w/wt8mh7fkf.css';
import '../../css/h/h4mxexe-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oua8-7eug"/><path clip-rule="evenodd" class="wt8mh7fkf"/><path clip-rule="evenodd" class="h4mxexe-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-zip-bold-duotone" {...props}></Icon>
