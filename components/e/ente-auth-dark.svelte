<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i093s-bce.css';
import '../../css/c/cawcmqbki.css';
import '../../css/f/fk33h5fcb.css';
import '../../css/i/i7ja3-5jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i093s-bce"/><path class="cawcmqbki"/><path class="fk33h5fcb"/><path class="i7ja3-5jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ente-auth-dark" {...props}></Icon>
