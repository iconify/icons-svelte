<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hdfol04mj.css';
import '../../css/b/b30bw2w4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="hdfol04mj"/><path class="b30bw2w4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:odnoklassniki" {...props}></Icon>
