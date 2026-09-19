<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr2he0bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":544,"height":512};
const content = `<path class="lr2he0bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chart-pie" {...props}></Icon>
