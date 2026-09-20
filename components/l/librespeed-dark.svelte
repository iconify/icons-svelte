<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec5wcebee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ec5wcebee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librespeed-dark" {...props}></Icon>
