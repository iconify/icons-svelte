<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1toveb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1toveb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-light" {...props}></Icon>
