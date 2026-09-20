<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koehhbc9o.css';
import '../../css/w/wqypsdb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="koehhbc9o"/><path class="wqypsdb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kiroshi" {...props}></Icon>
