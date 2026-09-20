<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f-f_sqb8q.css';
import '../../css/a/aicw3bbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<g class="cuyn6tgcc"><path class="f-f_sqb8q"/><path class="aicw3bbuy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:quora-circle" {...props}></Icon>
