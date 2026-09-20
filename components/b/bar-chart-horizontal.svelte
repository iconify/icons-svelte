<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg0_p6zxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg0_p6zxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bar-chart-horizontal" {...props}></Icon>
