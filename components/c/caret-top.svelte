<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6vurab3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h6vurab3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:caret-top" {...props}></Icon>
