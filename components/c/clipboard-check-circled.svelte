<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qqmv1h99a.css';
import '../../css/e/eyhpw0myq.css';
import '../../css/v/v_p5l6vke.css';
import '../../css/d/dsmb2pb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="qqmv1h99a"/><path class="eyhpw0myq"/><path class="v_p5l6vke"/><path class="dsmb2pb7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:clipboard-check-circled" {...props}></Icon>
