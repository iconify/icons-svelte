<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-nrxac0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e-nrxac0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:racetrack-cycling" {...props}></Icon>
