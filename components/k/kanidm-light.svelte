<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs34dhb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rs34dhb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kanidm-light" {...props}></Icon>
