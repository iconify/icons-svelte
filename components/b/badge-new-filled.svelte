<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/latvlcb9l.css';
import '../../css/p/pvotfl8ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGbDH6ubpA)"><path clip-rule="evenodd" class="latvlcb9l"/></g><defs><clipPath id="SVGbDH6ubpA"><path class="pvotfl8ci"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:badge-new-filled" {...props}></Icon>
