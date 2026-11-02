<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb8uykbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb8uykbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-gantt-fill" {...props}></Icon>
