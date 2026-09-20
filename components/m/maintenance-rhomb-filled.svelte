<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4zk5lb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4zk5lb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance-rhomb-filled" {...props}></Icon>
