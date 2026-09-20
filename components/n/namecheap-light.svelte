<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk8e7g4nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tk8e7g4nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:namecheap-light" {...props}></Icon>
