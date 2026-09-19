<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stxidc2sn.css';
import '../../css/w/w1nvnyp9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="stxidc2sn"/><path class="w1nvnyp9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:forgejo-wordmark" {...props}></Icon>
