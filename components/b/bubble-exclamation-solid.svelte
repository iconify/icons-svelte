<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8r8nxbmo.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="b8r8nxbmo clr-i-solid clr-i-solid-path-1"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:bubble-exclamation-solid" {...props}></Icon>
