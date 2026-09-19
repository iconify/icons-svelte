<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duy4fwuoh.css';
import '../../css/y/ym7s1o7nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="duy4fwuoh"/><path class="ym7s1o7nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bicycle-sharp" {...props}></Icon>
