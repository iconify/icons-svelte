<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dul5rebap.css';
import '../../css/w/wcgje-bvn.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 dul5rebap"/><path class="clr-i-solid clr-i-solid-path-2 wcgje-bvn"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:devices-solid" {...props}></Icon>
