<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swevlxb4e.css';
import '../../css/h/hgy1l_tlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="swevlxb4e"/><path class="hgy1l_tlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plus-20-bold" {...props}></Icon>
