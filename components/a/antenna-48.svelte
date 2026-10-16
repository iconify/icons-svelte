<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnzn_vsno.css';
import '../../css/v/vl-e_fb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dnzn_vsno"/><path class="vl-e_fb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:antenna-48" {...props}></Icon>
