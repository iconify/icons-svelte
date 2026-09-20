<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j19d1tb1x.css';
import '../../css/b/bamoiilsm.css';
import '../../css/g/glthabcxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j19d1tb1x"/><path class="bamoiilsm"/><path class="glthabcxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:box2-duotone" {...props}></Icon>
