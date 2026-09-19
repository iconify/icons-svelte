<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hd02y12rp.css';
import '../../css/a/as28f4qml.css';
import '../../css/u/ubbh73trt.css';
import '../../css/c/c9jjgfb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="hd02y12rp"/><path class="as28f4qml"/><path clip-rule="evenodd" class="ubbh73trt"/><path class="c9jjgfb6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:file-tips-one" {...props}></Icon>
