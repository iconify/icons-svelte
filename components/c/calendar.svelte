<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxrep1phr.css';
import '../../css/o/odkqjcchh.css';
import '../../css/u/uq5fhnb9e.css';
import '../../css/c/cxfni2ljt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hxrep1phr"/><circle class="odkqjcchh"/><circle class="uq5fhnb9e"/><circle class="cxfni2ljt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:calendar" {...props}></Icon>
