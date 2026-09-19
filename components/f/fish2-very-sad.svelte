<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn7foxpmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sn7foxpmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish2-very-sad" {...props}></Icon>
