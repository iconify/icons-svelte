<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pltokbbut.css';
import '../../css/t/ta2uc2b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="pltokbbut"/><path class="ta2uc2b5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-square-down" {...props}></Icon>
