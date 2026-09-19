<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxbiylbvh.css';
import '../../css/a/afnh3eg2a.css';
import '../../css/o/onw483rpz.css';
import '../../css/u/uj0djj1qw.css';
import '../../css/p/pgi2lcabh.css';
import '../../css/o/osn__dbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="uxbiylbvh"/><path class="afnh3eg2a"/><path class="onw483rpz"/><path class="uj0djj1qw"/><path class="pgi2lcabh"/><path class="osn__dbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bunnyside" {...props}></Icon>
