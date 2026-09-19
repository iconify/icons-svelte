<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rgd6yb9-y.css';
import '../../css/w/wazow3b1r.css';
import '../../css/s/s89r_abgl.css';
import '../../css/p/ptfkqx5cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="rgd6yb9-y"/><rect class="wazow3b1r"/><rect class="s89r_abgl"/><path class="ptfkqx5cc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:projector-one" {...props}></Icon>
