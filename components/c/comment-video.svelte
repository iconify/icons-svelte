<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unsn_va9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="unsn_va9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-video" {...props}></Icon>
