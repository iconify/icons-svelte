<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ltc0qfcyk.css';
import '../../css/n/n7jhs1bil.css';
import '../../css/e/ezbn6olzb.css';
import '../../css/b/b9vzy7r5m.css';
import '../../css/v/v07q0rm0c.css';
import '../../css/s/st8r_y1jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="ltc0qfcyk"/><path clip-rule="evenodd" class="n7jhs1bil"/><path class="ezbn6olzb"/><path class="b9vzy7r5m"/><path clip-rule="evenodd" class="v07q0rm0c"/><path class="st8r_y1jl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:cv-off" {...props}></Icon>
