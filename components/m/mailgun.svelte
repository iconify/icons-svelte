<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y412vxlxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y412vxlxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailgun" {...props}></Icon>
