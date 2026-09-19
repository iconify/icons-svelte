<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orxt2w0nn.css';
import '../../css/y/ys2g1yc6p.css';
import '../../css/n/n4j_19b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="orxt2w0nn"/><path class="ys2g1yc6p"/><path class="n4j_19b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:heart-broken" {...props}></Icon>
