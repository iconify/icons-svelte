<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no7fnibtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no7fnibtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-no-axes-gantt-fill" {...props}></Icon>
