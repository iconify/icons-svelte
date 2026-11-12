<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r61cogx2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r61cogx2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oracle-light" {...props}></Icon>
