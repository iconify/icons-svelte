<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f386ljber.css';
import '../../css/x/xlllqtwpy.css';
import '../../css/b/b4wadacto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="bi12bsetm"><path class="f386ljber"/><circle class="xlllqtwpy"/><path class="b4wadacto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:gps" {...props}></Icon>
