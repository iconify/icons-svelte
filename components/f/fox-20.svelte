<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyptepbli.css';
import '../../css/t/tmu41y1sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zyptepbli"/><path class="tmu41y1sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fox-20" {...props}></Icon>
