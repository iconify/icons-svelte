<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjo1_vbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjo1_vbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alby-hub-light" {...props}></Icon>
