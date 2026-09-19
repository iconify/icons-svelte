<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/w/w6r6sxrzo.css';
import '../../css/o/omlunobmw.css';
import '../../css/b/bhx3wd61g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="w6r6sxrzo"/><path class="omlunobmw"/><path class="bhx3wd61g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:code" {...props}></Icon>
