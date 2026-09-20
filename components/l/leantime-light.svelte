<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy7q-6bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gy7q-6bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:leantime-light" {...props}></Icon>
