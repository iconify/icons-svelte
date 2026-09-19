<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-vvoub4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-vvoub4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:deno" {...props}></Icon>
