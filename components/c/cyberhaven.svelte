<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi-hyiv2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qi-hyiv2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cyberhaven" {...props}></Icon>
