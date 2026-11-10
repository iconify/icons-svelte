<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/t/tje_rgu0e.css';
import '../../css/b/b8uhdggbp.css';
import '../../css/a/asmyp4_rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="tje_rgu0e"/><path class="b8uhdggbp"/><path class="asmyp4_rf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:banknote" {...props}></Icon>
