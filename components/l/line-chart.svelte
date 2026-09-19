<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzk2onifa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzk2onifa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:line-chart" {...props}></Icon>
