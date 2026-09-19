<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0tmkpb-w.css';
import '../../css/u/u_fqzdbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<rect class="g0tmkpb-w"/><path class="u_fqzdbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:mobile-phone-stroke-12" {...props}></Icon>
