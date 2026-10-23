<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2scli3dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2scli3dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-chart-column" {...props}></Icon>
