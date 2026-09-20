<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e76g5pbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e76g5pbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-chart-column" {...props}></Icon>
