<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pppldzb5a.css';
import '../../css/y/y71myfbar.css';
import '../../css/c/c_yq6m48d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pppldzb5a"/><path clip-rule="evenodd" class="y71myfbar"/><path class="c_yq6m48d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:loop" {...props}></Icon>
