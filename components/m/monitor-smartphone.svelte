<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vlwthcb-o.css';
import '../../css/s/szv0abf7p.css';
import '../../css/t/t0po4kjqp.css';
import '../../css/q/qzuozacwt.css';
import '../../css/g/gw4m2objp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vlwthcb-o"/><path class="szv0abf7p"/><path class="t0po4kjqp"/><path class="qzuozacwt"/><path class="gw4m2objp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:monitor-smartphone" {...props}></Icon>
