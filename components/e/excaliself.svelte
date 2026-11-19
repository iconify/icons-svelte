<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io9_9gbtr.css';
import '../../css/k/koafcjh_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="io9_9gbtr"/><path class="koafcjh_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:excaliself" {...props}></Icon>
