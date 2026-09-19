<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ysm6kgbvw.css';
import '../../css/w/w3rad0bwq.css';
import '../../css/c/cloky08hd.css';
import '../../css/x/xi8a1wbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="ysm6kgbvw"/><path class="w3rad0bwq"/><circle class="cloky08hd"/><circle class="xi8a1wbvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:mv" {...props}></Icon>
