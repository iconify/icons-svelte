<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxj7r4rhc.css';
import '../../css/x/x9cx8dvbi.css';
import '../../css/u/usalp6zbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxj7r4rhc"/><path class="x9cx8dvbi"/><path class="usalp6zbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:candy" {...props}></Icon>
