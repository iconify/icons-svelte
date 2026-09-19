<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aljgoxbom.css';
import '../../css/i/ii4z4oljf.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="aljgoxbom clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 ii4z4oljf"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:pause-line" {...props}></Icon>
