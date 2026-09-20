<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bph7wduct.css';
import '../../css/a/a2u7q4nxu.css';
import '../../css/v/vjnt0fbaj.css';
import '../../css/m/m52v0xb7c.css';
import '../../css/z/z3-4c0wrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bph7wduct"/><path class="a2u7q4nxu"/><path class="vjnt0fbaj"/><path class="m52v0xb7c"/><path class="z3-4c0wrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relaticle-dark" {...props}></Icon>
