<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/x/xn4903-ui.css';
import '../../css/w/w7m3uccqr.css';
import '../../css/w/wl50mf2jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="xn4903-ui"/><path class="w7m3uccqr"/><path class="wl50mf2jv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:person-plus" {...props}></Icon>
