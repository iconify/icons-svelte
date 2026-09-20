<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmu-53b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tmu-53b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dub-light" {...props}></Icon>
