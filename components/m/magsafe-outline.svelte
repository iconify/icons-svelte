<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv2xbp3ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gv2xbp3ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:magsafe-outline" {...props}></Icon>
