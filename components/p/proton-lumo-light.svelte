<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjdhlo7vy.css';
import '../../css/a/atca9c2ie.css';
import '../../css/s/s9wdzbc7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjdhlo7vy"/><path class="atca9c2ie"/><path class="s9wdzbc7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-lumo-light" {...props}></Icon>
