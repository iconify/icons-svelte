<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e53pislml.css';
import '../../css/z/zzm1u_hwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e53pislml"/><path class="zzm1u_hwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hawser-dark" {...props}></Icon>
