<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mozc1bb5c.css';
import '../../css/a/a1ypjyb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mozc1bb5c"/><path class="a1ypjyb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:phonewithpage" {...props}></Icon>
