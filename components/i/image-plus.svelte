<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f8le2jbey.css';
import '../../css/o/ol5--vb1y.css';
import '../../css/t/t10685b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f8le2jbey"/><path clip-rule="evenodd" class="ol5--vb1y"/><path class="t10685b9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:image-plus" {...props}></Icon>
