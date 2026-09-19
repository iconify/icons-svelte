<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrh4_jbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xrh4_jbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:music-note" {...props}></Icon>
