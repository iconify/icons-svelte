<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3i8uzbyg.css';
import '../../css/e/edwthhmnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q3i8uzbyg"/><path class="edwthhmnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:map-location-filled" {...props}></Icon>
