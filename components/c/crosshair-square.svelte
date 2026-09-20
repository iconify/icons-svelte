<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he3ym7_zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he3ym7_zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:crosshair-square" {...props}></Icon>
