<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggmqpnbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ggmqpnbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:box-outline" {...props}></Icon>
