<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byrz3kh6s.css';
import '../../css/y/y2h-ot9zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="byrz3kh6s"/><path class="y2h-ot9zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-tag-manager-light" {...props}></Icon>
