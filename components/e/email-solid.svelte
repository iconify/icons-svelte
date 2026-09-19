<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc4a8abel.css';
import '../../css/b/bkcl-r-9o.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 pc4a8abel"/><path class="bkcl-r-9o clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:email-solid" {...props}></Icon>
