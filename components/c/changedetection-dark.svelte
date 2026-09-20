<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3k__wbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p3k__wbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:changedetection-dark" {...props}></Icon>
