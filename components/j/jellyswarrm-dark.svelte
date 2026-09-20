<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehcptp5io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ehcptp5io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jellyswarrm-dark" {...props}></Icon>
