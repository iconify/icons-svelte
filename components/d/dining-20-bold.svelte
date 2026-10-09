<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjr53p4wm.css';
import '../../css/j/jx_02mklt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xjr53p4wm"/><path class="jx_02mklt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dining-20-bold" {...props}></Icon>
