<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfsw2acuj.css';
import '../../css/o/oiv_48byp.css';
import '../../css/p/pvywatupn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lfsw2acuj"/><path class="oiv_48byp"/><path class="pvywatupn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kite-20" {...props}></Icon>
