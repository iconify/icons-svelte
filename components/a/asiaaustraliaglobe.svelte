<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4dm09b_v.css';
import '../../css/s/scg0arb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4dm09b_v"/><path class="scg0arb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:asiaaustraliaglobe" {...props}></Icon>
