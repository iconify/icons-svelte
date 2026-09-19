<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d145pkbyl.css';
import '../../css/u/u1jtw-d9c.css';
import '../../css/e/ejksmvbap.css';
import '../../css/s/shvrguwxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d145pkbyl"/><path class="u1jtw-d9c"/><path class="ejksmvbap"/><path class="shvrguwxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-qr-scanner" {...props}></Icon>
