<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/la706ebvw.css';
import '../../css/q/qnb0a6bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="la706ebvw"/><path class="qnb0a6bwg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:black-cat-solid" {...props}></Icon>
