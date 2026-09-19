<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/j/j_jy0mb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m4l-9ybuj"/><path class="j_jy0mb8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:relieved-face-light" {...props}></Icon>
