<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw0g3psjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bw0g3psjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-insights-light" {...props}></Icon>
