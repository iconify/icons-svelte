<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swmlmj4nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="swmlmj4nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:namecheap-dark" {...props}></Icon>
