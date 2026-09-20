<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjmw7zpnx.css';
import '../../css/o/oz3hiebwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rjmw7zpnx"/><path class="oz3hiebwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:copilot-16" {...props}></Icon>
