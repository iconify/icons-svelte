<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o7i3yvf1s.css';
import '../../css/h/hd-x4gbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o7i3yvf1s"/><path class="hd-x4gbpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:clipboard-list" {...props}></Icon>
