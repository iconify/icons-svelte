<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lah38-bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lah38-bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kopia" {...props}></Icon>
