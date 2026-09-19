<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gehy3pb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gehy3pb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:interlocking-rings-stroke-12" {...props}></Icon>
