<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwetwse_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwetwse_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:at-sharp" {...props}></Icon>
