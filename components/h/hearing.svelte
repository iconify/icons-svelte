<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2b_qbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="t_2b_qbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hearing" {...props}></Icon>
