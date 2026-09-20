<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od4ok1_9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="od4ok1_9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coneshare-light" {...props}></Icon>
