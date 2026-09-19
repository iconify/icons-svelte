<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1udlpbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="m1udlpbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pull" {...props}></Icon>
