<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs1tkhbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rs1tkhbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:briefcase-sharp" {...props}></Icon>
