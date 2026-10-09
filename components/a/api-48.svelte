<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzeztmj2w.css';
import '../../css/j/jq2f_o2_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mzeztmj2w"/><path class="jq2f_o2_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:api-48" {...props}></Icon>
