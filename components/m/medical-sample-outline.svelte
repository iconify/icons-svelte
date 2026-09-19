<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r3uyncqxs.css';
import '../../css/d/dyzltge-g.css';
import '../../css/r/rqniv96bp.css';
import '../../css/m/m9c61dktf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="r3uyncqxs"/><path class="dyzltge-g"/><path class="rqniv96bp"/><path class="m9c61dktf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:medical-sample-outline" {...props}></Icon>
