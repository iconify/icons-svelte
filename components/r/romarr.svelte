<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw3j8x2vl.css';
import '../../css/s/sog-c-_ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rw3j8x2vl"/><path class="sog-c-_ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:romarr" {...props}></Icon>
