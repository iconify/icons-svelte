<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-6vw4asl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-6vw4asl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orange-isp-dark" {...props}></Icon>
