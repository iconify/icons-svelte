<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_q7sqpql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="g_q7sqpql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:paper" {...props}></Icon>
