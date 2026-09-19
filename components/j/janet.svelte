<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fes3r4mpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":512};
const content = `<path class="fes3r4mpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:janet" {...props}></Icon>
