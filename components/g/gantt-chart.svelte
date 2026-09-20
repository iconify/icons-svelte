<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxec7rbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxec7rbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:gantt-chart" {...props}></Icon>
