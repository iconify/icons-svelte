<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pjit7db-i.css';
import '../../css/e/e0cwhzbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="pjit7db-i"/><path class="e0cwhzbpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:bow-tie-flat" {...props}></Icon>
