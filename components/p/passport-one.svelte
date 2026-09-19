<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/f-84rkb8o.css';
import '../../css/e/e-51jmb7g.css';
import '../../css/i/i68jrdbcu.css';
import '../../css/m/m1tppxbrb.css';
import '../../css/f/fc65m0hvb.css';
import '../../css/g/gca4q30qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="f-84rkb8o"/><rect transform="rotate(-90 13 44)" class="e-51jmb7g"/><circle class="i68jrdbcu"/><path class="m1tppxbrb"/><path class="fc65m0hvb"/><path class="gca4q30qy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:passport-one" {...props}></Icon>
