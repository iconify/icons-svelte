<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ns9xbsl.css';
import '../../css/g/grio-8blz.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/q/qvksvzdwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q0ns9xbsl"/><path class="grio-8blz"/><path class="aqsnv9bnd"/><path class="qvksvzdwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-check-20-bold" {...props}></Icon>
