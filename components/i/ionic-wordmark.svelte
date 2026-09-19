<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thpy47d_f.css';
import '../../css/l/lwha5_b5g.css';
import '../../css/q/qm9invowl.css';
import '../../css/r/rm1klhb5f.css';
import '../../css/w/wb4efo_qd.css';
import '../../css/e/ecf5uvhjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="thpy47d_f"><path class="lwha5_b5g"/><circle class="qm9invowl"/><circle class="rm1klhb5f"/><circle class="wb4efo_qd"/><path class="ecf5uvhjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ionic-wordmark" {...props}></Icon>
