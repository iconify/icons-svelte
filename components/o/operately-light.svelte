<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k82zlrxzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k82zlrxzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:operately-light" {...props}></Icon>
