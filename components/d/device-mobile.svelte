<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4dcppbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l4dcppbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:device-mobile" {...props}></Icon>
