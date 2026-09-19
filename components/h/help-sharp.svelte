<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuyntrele.css';
import '../../css/y/y8ocdrfcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fuyntrele"/><rect class="y8ocdrfcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:help-sharp" {...props}></Icon>
