<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g64y_l5-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g64y_l5-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-frame-light" {...props}></Icon>
