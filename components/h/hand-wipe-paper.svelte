<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/crvfg_zef.css';
import '../../css/a/a30gdttzf.css';
import '../../css/b/bo93y_ztc.css';
import '../../css/s/s26qisbtl.css';
import '../../css/s/scaplnjbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="crvfg_zef"/><path class="a30gdttzf"/><path clip-rule="evenodd" class="bo93y_ztc"/><path clip-rule="evenodd" class="s26qisbtl"/><path clip-rule="evenodd" class="scaplnjbf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hand-wipe-paper" {...props}></Icon>
