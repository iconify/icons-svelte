<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u04dskhoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u04dskhoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oracle-dark" {...props}></Icon>
