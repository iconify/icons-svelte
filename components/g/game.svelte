<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/e/ehssdsxzo.css';
import '../../css/p/plakrxbhx.css';
import '../../css/a/ahdaw7x5b.css';
import '../../css/z/z7e_plawd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="ehssdsxzo"/><path class="plakrxbhx"/><path class="ahdaw7x5b"/><path class="z7e_plawd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:game" {...props}></Icon>
