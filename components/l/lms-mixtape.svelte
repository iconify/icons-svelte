<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj9--rywt.css';
import '../../css/r/rr9a01bpl.css';
import '../../css/d/dz4yw6hux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oj9--rywt"/><path class="rr9a01bpl"/><path class="dz4yw6hux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lms-mixtape" {...props}></Icon>
