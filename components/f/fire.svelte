<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5gdpl4fa.css';
import '../../css/i/if6xh6bvd.css';
import '../../css/y/yo7go3bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z5gdpl4fa"/><path class="if6xh6bvd"/><path class="yo7go3bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:fire" {...props}></Icon>
