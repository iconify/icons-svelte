<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8gtx7ddi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r8gtx7ddi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-right-48-bold" {...props}></Icon>
