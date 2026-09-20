<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_3n8na5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_3n8na5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockform" {...props}></Icon>
