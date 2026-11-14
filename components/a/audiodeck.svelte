<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puwug5bgg.css';
import '../../css/h/ht9cs5buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="puwug5bgg"/><path class="ht9cs5buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiodeck" {...props}></Icon>
