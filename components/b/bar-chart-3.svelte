<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtkbmnbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtkbmnbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bar-chart-3" {...props}></Icon>
