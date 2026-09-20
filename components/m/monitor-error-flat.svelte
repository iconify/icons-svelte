<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uoitckm8z.css';
import '../../css/j/j4c_x5bwc.css';
import '../../css/w/w6zuj4k8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uoitckm8z"/><path class="j4c_x5bwc"/><path class="w6zuj4k8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:monitor-error-flat" {...props}></Icon>
