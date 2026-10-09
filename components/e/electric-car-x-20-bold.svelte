<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ns9xbsl.css';
import '../../css/g/grio-8blz.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/n/nj9yfcx7y.css';
import '../../css/b/b325a1bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q0ns9xbsl"/><path class="grio-8blz"/><path class="aqsnv9bnd"/><path class="nj9yfcx7y"/><path class="b325a1bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-x-20-bold" {...props}></Icon>
