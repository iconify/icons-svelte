<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz7iaspvb.css';
import '../../css/y/y2h-ot9zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oz7iaspvb"/><path class="y2h-ot9zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-tag-manager-light" {...props}></Icon>
