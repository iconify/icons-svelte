<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkweo9bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qkweo9bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cobalt-light" {...props}></Icon>
