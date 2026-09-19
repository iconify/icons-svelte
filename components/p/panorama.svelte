<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9crkbcmi.css';
import '../../css/v/vywszeb-t.css';
import '../../css/d/d_5hd163w.css';
import '../../css/m/m-cozdbmp.css';
import '../../css/u/uxqvqub-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m9crkbcmi"/><path class="vywszeb-t"/><path class="d_5hd163w"/><path class="m-cozdbmp"/><ellipse class="uxqvqub-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:panorama" {...props}></Icon>
