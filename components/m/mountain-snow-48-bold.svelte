<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg1-fhq_s.css';
import '../../css/p/p9d7ykejn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pg1-fhq_s"/><path class="p9d7ykejn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-snow-48-bold" {...props}></Icon>
