<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2priwbjg.css';
import '../../css/k/k4jeo3qws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k2priwbjg"/><path class="k4jeo3qws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:invoice" {...props}></Icon>
