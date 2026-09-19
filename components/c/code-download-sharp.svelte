<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhfpk-x5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhfpk-x5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:code-download-sharp" {...props}></Icon>
