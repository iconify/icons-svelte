<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yql7wlbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yql7wlbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:certimate-light" {...props}></Icon>
