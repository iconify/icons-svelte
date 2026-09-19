<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj9rjo1dz.css';
import '../../css/g/g2ibk0p0r.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 gj9rjo1dz"/><path class="clr-i-solid clr-i-solid-path-2 g2ibk0p0r"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:library-solid" {...props}></Icon>
