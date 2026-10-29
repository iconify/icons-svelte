<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/la3wq9fod.css';
import '../../css/c/cocrkvbsc.css';
import '../../css/p/prjwt6bag.css';
import '../../css/q/qyldeu1it.css';
import '../../css/m/mmj9frbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="la3wq9fod wm-deco"/><path class="cocrkvbsc wm-deco"/><path class="prjwt6bag wm-deco"/><path class="qyldeu1it"/><path class="mmj9frbti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pen-tool-blueprint" {...props}></Icon>
