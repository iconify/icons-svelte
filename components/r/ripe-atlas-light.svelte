<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpxhnwrkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpxhnwrkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ripe-atlas-light" {...props}></Icon>
