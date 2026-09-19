<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5aywsbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5aywsbyj b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pie-chart-alt-2-filled" {...props}></Icon>
