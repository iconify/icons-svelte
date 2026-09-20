<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whoyo1bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whoyo1bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:multi-scrobbler-light" {...props}></Icon>
