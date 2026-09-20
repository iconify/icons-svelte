<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrkvb8gxl.css';
import '../../css/p/pk3sogrrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lrkvb8gxl"/><path class="pk3sogrrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:codescan-16" {...props}></Icon>
