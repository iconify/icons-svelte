<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfzpr-bpb.css';
import '../../css/v/vllkojbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jfzpr-bpb"/><path class="vllkojbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:egg-20" {...props}></Icon>
