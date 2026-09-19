<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqv_ljb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="aqv_ljb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hourglass" {...props}></Icon>
