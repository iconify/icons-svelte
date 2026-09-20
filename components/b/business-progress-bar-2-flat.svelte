<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f6zu09hhk.css';
import '../../css/a/afl5k8dzu.css';
import '../../css/n/na4f4--6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f6zu09hhk"/><path class="afl5k8dzu"/><path class="na4f4--6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:business-progress-bar-2-flat" {...props}></Icon>
