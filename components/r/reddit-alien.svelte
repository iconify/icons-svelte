<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og-oztl2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="og-oztl2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:reddit-alien" {...props}></Icon>
