<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z4n05zl7r.css';
import '../../css/g/gbvnb5bkp.css';
import '../../css/e/ejy_ic09t.css';
import '../../css/n/nbfw7rpxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="z4n05zl7r"/><path class="gbvnb5bkp"/><path class="ejy_ic09t"/><path clip-rule="evenodd" class="nbfw7rpxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:file-question" {...props}></Icon>
