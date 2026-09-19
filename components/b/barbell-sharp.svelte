<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib84k77zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ib84k77zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:barbell-sharp" {...props}></Icon>
