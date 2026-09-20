<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm3bjm3aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rm3bjm3aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connector-chart" {...props}></Icon>
