<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_leqbidc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="q_leqbidc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:arttext4" {...props}></Icon>
