<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6515jepd.css';
import '../../css/c/c97n50bhy.css';
import '../../css/z/z1zkdbgsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6515jepd"/><path class="c97n50bhy"/><path class="z1zkdbgsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-lumo-dark" {...props}></Icon>
