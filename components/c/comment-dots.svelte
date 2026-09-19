<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpdlfs5oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dpdlfs5oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:comment-dots" {...props}></Icon>
