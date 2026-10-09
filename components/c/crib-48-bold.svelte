<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcb49wu3o.css';
import '../../css/f/ftfqnvhwn.css';
import '../../css/l/lz4wfsojb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wcb49wu3o"/><path class="ftfqnvhwn"/><path class="lz4wfsojb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crib-48-bold" {...props}></Icon>
