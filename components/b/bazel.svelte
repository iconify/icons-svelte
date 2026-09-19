<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1sze7i_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y1sze7i_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bazel" {...props}></Icon>
