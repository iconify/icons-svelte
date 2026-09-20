<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-alm_vye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r-alm_vye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:limesurvey" {...props}></Icon>
