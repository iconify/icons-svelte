<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8vn53lfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n8vn53lfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:couch-filled" {...props}></Icon>
