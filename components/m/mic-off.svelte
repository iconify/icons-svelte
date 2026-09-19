<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty51eibwy.css';
import '../../css/p/pg7d3m2ja.css';
import '../../css/y/ybvnaxjzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ty51eibwy"/><path class="pg7d3m2ja"/><path class="ybvnaxjzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mic-off" {...props}></Icon>
