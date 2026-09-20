<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd5rqgb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yd5rqgb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:garage-light" {...props}></Icon>
