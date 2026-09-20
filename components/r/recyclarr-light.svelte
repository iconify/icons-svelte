<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhnn1_t4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhnn1_t4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:recyclarr-light" {...props}></Icon>
