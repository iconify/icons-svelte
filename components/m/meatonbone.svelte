<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6_cvul6v.css';
import '../../css/b/bo2v11vwg.css';
import '../../css/n/n7haok96c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6_cvul6v"/><path class="bo2v11vwg"/><path class="n7haok96c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:meatonbone" {...props}></Icon>
