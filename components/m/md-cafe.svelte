<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7o_ndblm.css';
import '../../css/o/okqxufbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7o_ndblm"/><path class="okqxufbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-cafe" {...props}></Icon>
