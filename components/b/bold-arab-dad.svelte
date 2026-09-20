<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzdnmsb-q.css';
import '../../css/t/ty_2is9tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dzdnmsb-q"/><circle class="ty_2is9tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-arab-dad" {...props}></Icon>
