<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtgd7zbyl.css';
import '../../css/w/ws3ki_htx.css';
import '../../css/m/m3p5ncbjq.css';
import '../../css/p/pphcryv5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qtgd7zbyl"/><path class="ws3ki_htx"/><path class="m3p5ncbjq"/><path class="pphcryv5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:library-add" {...props}></Icon>
