<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9ncz__nf.css';
import '../../css/u/u-c3y7bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h9ncz__nf"/><path class="u-c3y7bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:location-pin" {...props}></Icon>
