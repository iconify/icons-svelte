<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w29l6ybjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w29l6ybjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haproxy-dark" {...props}></Icon>
