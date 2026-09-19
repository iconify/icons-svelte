<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izt-xbfer.css';
import '../../css/b/buyojelvy.css';
import '../../css/q/qk1bvjeqe.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 izt-xbfer"/><path class="buyojelvy clr-i-solid clr-i-solid-path-2"/><path class="clr-i-solid clr-i-solid-path-3 qk1bvjeqe"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:eye-hide-solid" {...props}></Icon>
