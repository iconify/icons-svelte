<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0p-n6nhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0p-n6nhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dolibarr-light" {...props}></Icon>
