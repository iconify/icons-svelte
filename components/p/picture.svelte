<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zkbga2bms.css';
import '../../css/m/m0-54lvnp.css';
import '../../css/i/i9hetd4rr.css';
import '../../css/m/m6hk46bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 3)" class="bi12bsetm"><g class="zkbga2bms"><path class="m0-54lvnp"/><path class="i9hetd4rr"/></g><circle class="m6hk46bel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:picture" {...props}></Icon>
