<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uoitckm8z.css';
import '../../css/f/f88pp0k3b.css';
import '../../css/g/gnzhvkwao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uoitckm8z"/><path class="f88pp0k3b"/><path class="gnzhvkwao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:code-monitor-1-flat" {...props}></Icon>
