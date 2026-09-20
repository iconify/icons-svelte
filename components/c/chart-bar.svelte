<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4f2kpbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4f2kpbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-bar" {...props}></Icon>
