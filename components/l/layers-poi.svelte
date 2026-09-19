<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9tbpdr2g.css';
import '../../css/t/tf2al91ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k9tbpdr2g"/><path class="tf2al91ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layers-poi" {...props}></Icon>
