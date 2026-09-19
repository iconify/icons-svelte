<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6d2y6bir.css';
import '../../css/x/x1kizjb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u6d2y6bir"/><path class="x1kizjb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:document-lock-sharp" {...props}></Icon>
