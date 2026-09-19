<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxnfp4_ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cxnfp4_ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:briefcase" {...props}></Icon>
