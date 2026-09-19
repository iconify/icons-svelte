<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0jv209hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e0jv209hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:google-allo" {...props}></Icon>
