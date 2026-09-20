<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q92a6obvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q92a6obvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gandi" {...props}></Icon>
