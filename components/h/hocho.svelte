<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhl50ubkh.css';
import '../../css/s/s05wzqbji.css';
import '../../css/t/ti-1rqbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhl50ubkh"/><path class="s05wzqbji"/><path class="ti-1rqbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:hocho" {...props}></Icon>
