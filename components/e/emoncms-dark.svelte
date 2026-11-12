<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq7gawjkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zq7gawjkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emoncms-dark" {...props}></Icon>
