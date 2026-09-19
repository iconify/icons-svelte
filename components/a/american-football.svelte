<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ati6izcqr.css';
import '../../css/o/oeud78yma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ati6izcqr"/><path class="oeud78yma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:american-football" {...props}></Icon>
