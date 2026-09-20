<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwotdib6l.css';
import '../../css/b/bhhw35bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nwotdib6l"/><rect class="bhhw35bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:compute" {...props}></Icon>
