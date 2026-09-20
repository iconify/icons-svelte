<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3-4pu7qp.css';
import '../../css/l/l3r2gvztf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s3-4pu7qp"/><path class="l3r2gvztf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:curator-bookmarks" {...props}></Icon>
