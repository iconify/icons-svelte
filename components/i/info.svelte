<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nedktqbjv.css';
import '../../css/r/rayd42qzh.css';
import '../../css/h/h88-h-uwe.css';
import '../../css/j/j8diwbuaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="nedktqbjv"/><path clip-rule="evenodd" class="rayd42qzh"/><path class="h88-h-uwe"/><path class="j8diwbuaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:info" {...props}></Icon>
