<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/t/t79nqfb1n.css';
import '../../css/o/o9pfyqqty.css';
import '../../css/b/bulvyxg5m.css';
import '../../css/w/wf5_z4p1g.css';
import '../../css/e/eqev2dbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="t79nqfb1n"/><path class="o9pfyqqty"/><path class="bulvyxg5m"/><path class="wf5_z4p1g"/><path class="eqev2dbms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:hand-point-open" {...props}></Icon>
