<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alx985b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="alx985b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:railway-halt-14" {...props}></Icon>
