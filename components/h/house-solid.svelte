<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_inqrbwp.css';
import '../../css/a/ad1wvybmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="r_inqrbwp"/><path class="ad1wvybmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:house-solid" {...props}></Icon>
