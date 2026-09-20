<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg7wfnrsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kg7wfnrsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:capsule-pill-and-rx-symbol" {...props}></Icon>
