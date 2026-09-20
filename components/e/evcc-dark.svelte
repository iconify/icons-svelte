<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eff2g6_ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eff2g6_ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:evcc-dark" {...props}></Icon>
