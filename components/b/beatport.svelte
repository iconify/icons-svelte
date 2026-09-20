<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pdy0rb19w.css';
import '../../css/j/jw8cvyb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5.5};
const content = `<g class="cuyn6tgcc"><path class="pdy0rb19w"/><path class="jw8cvyb2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:beatport" {...props}></Icon>
