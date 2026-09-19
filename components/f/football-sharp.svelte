<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgiziy1ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zgiziy1ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:football-sharp" {...props}></Icon>
