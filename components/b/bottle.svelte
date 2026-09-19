<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/i/i6eudtbje.css';
import '../../css/q/q4-zvdwys.css';
import '../../css/j/jb7mlffim.css';
import '../../css/b/b77ks6bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="i6eudtbje"/><path clip-rule="evenodd" class="q4-zvdwys"/><path class="jb7mlffim"/><path class="b77ks6bmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bottle" {...props}></Icon>
