<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n82dipk4k.css';
import '../../css/z/z55h80buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":75,"height":75};
const content = `<circle class="n82dipk4k"/><path class="z55h80buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:obs" {...props}></Icon>
