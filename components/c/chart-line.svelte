<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_x46zk6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g_x46zk6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chart-line" {...props}></Icon>
